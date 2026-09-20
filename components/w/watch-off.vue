<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wjbeh-boq"/><path clip-rule="evenodd" class="ayv09uboo"/><path clip-rule="evenodd" class="qeekmvyuo"/><path clip-rule="evenodd" class="wk0g5fs9w"/><path clip-rule="evenodd" class="oxekprb6o"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:watch-off" /></template>
<style>
.ayv09uboo {
  fill-rule: evenodd;
  d: path("M10 7.75a.75.75 0 0 1 .75.75V10a.75.75 0 0 1-1.5 0V8.5a.75.75 0 0 1 .75-.75");
}

.cuyn6tgcc {
  fill: currentColor;
}

.oxekprb6o {
  fill-rule: evenodd;
  d: path("M7.5 17.5a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1");
}

.qeekmvyuo {
  fill-rule: evenodd;
  d: path("M12.25 10a.75.75 0 0 1-.75.75H10a.75.75 0 0 1 0-1.5h1.5a.75.75 0 0 1 .75.75M7.5 2.5a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1");
}

.wjbeh-boq {
  fill-rule: evenodd;
  d: path("M10 6.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7M4.5 10a5.5 5.5 0 1 1 11 0a5.5 5.5 0 0 1-11 0");
}

.wk0g5fs9w {
  fill-rule: evenodd;
  d: path("M8.775 1.538a1 1 0 0 1 .687 1.237l-1 3.5a1 1 0 1 1-1.924-.55l1-3.5a1 1 0 0 1 1.237-.687m0 16.924a1 1 0 0 0 .687-1.237l-1-3.5a1 1 0 1 0-1.924.55l1 3.5a1 1 0 0 0 1.237.687m2.45 0a1 1 0 0 1-.686-1.237l1-3.5a1 1 0 1 1 1.922.55l-1 3.5a1 1 0 0 1-1.236.687m0-16.924a1 1 0 0 0-.686 1.237l1 3.5a1 1 0 1 0 1.922-.55l-1-3.5a1 1 0 0 0-1.236-.687");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
