<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dn-8lcbzk"/><path class="sd2-5e_fr"/><ellipse class="qh4n-5b1w"/><ellipse class="had5fbb1i"/><path class="pfglehbxw"/><path class="nkbmj6fwh"/><ellipse class="r_mxglhib"/><path class="vglu0mngj"/><path class="dfjmvsrov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:roll-of-paper" /></template>
<style>
.dfjmvsrov {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M16.5 13H15v-1h1.5c.275 0 .5.225.5.5s-.225.5-.5.5m4 0h-2c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h2c.275 0 .5.225.5.5s-.225.5-.5.5m4 0h-2c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h2c.275 0 .5.225.5.5s-.225.5-.5.5m4 0h-2c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h2c.275 0 .5.225.5.5s-.225.5-.5.5m3.5 0h-1.5c-.275 0-.5-.225-.5-.5s.225-.5.5-.5H32zM16.5 25H15v-1h1.5c.275 0 .5.225.5.5s-.225.5-.5.5m4 0h-2c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h2c.275 0 .5.225.5.5s-.225.5-.5.5m4 0h-2c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h2c.275 0 .5.225.5.5s-.225.5-.5.5m4 0h-2c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h2c.275 0 .5.225.5.5s-.225.5-.5.5m3.5 0h-1.5c-.275 0-.5-.225-.5-.5s.225-.5.5-.5H32z");
}

.dn-8lcbzk {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M7 0h17v24H7z");
}

.had5fbb1i {
  cx: 24px;
  cy: 12px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  rx: 8px;
  ry: 12px;
}

.nkbmj6fwh {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M32 12c0-4.924-1.979-9.15-4.807-11H11.322C13.549 3.284 15 7.316 15 12v14c.429 5.683 2.683 8.3 3.383 9H35.05C33.867 33.496 32 30.151 32 24z");
}

.pfglehbxw {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M32 12v12c0 9 4 12 4 12H18s-4-3-4-12V11z");
}

.qh4n-5b1w {
  cx: 7px;
  cy: 12px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 7px;
  ry: 12px;
}

.r_mxglhib {
  cx: 6px;
  cy: 12px;
  fill: var(--svg-color--99aab5, #99aab5);
  rx: 3px;
  ry: 5px;
}

.sd2-5e_fr {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M7 12h17v12H7z");
}

.vglu0mngj {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M3.25 10.01C3.712 8.24 4.768 7 6 7c1.657 0 3 2.239 3 5c0 .616-.076 1.2-.198 1.745c-.649-2.088-2.871-3.642-5.552-3.735");
}

</style>
