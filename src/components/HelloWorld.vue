<template>
  <div class="hello">
    <div class="e1">
      <h1>echart1</h1>
      <echart1/>
    </div>
    <div class="e1">
      <h1>echartsRequestAnimationFrameSetTimeout</h1>
      <echartsRequestAnimationFrameSetTimeout/>
    </div>
    <div class="e1">
      <h1>echartsRequestAnimationFrameSetTimeout2</h1>
      <echartsRequestAnimationFrameSetTimeout2/>
    </div>
    <div class="e1">
      <h1>echartsRequestAnimationFrame</h1>
      <echartsRequestAnimationFrame/>
    </div>
    <div class="e1">
      <h1>echartsRequestAnimationFrame2</h1>
      <echartsRequestAnimationFrame2/>
    </div>
    <div class="e1">
      <h1>echartSetInterval</h1>
      <echartSetInterval/>
    </div>
    <div class="e1">
      <h1>echartSetInterval2</h1>
      <echartSetInterval2/>
    </div>
  </div>
</template>

<script>
import echart1 from "@/components/echart1";
import echartsRequestAnimationFrameSetTimeout from "@/components/echartsRequestAnimationFrameSetTimeout";
import echartsRequestAnimationFrameSetTimeout2 from "@/components/echartsRequestAnimationFrameSetTimeout2";
import echartsRequestAnimationFrame from "@/components/echartsRequestAnimationFrame";
import echartsRequestAnimationFrame2 from "@/components/echartsRequestAnimationFrame2";
import echartSetInterval from "@/components/echartSetInterval";
import echartSetInterval2 from "@/components/echartSetInterval2";
export default {
  name: "HelloWorld",
  components: {
    echart1,
    echartsRequestAnimationFrameSetTimeout,
    echartsRequestAnimationFrameSetTimeout2,
    echartsRequestAnimationFrame,
    echartsRequestAnimationFrame2,
    echartSetInterval,
    echartSetInterval2
  },
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  justify-content: flex-start;
  align-items: center;
}
.e1 {
  /*   display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-around;
  align-items: center; */
  margin-bottom: 40px;
}
</style>
