<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="e8ozzgbcf"/><path class="lovvf5btp"/><path class="wiele__nh"/><path class="u-kz_tbod"/><path class="jskm1jhfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:watch" /></template>
<style>
.e8ozzgbcf {
  d: path("M10 6.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7M4.5 10a5.5 5.5 0 1 1 11 0a5.5 5.5 0 0 1-11 0");
}

.jskm1jhfi {
  d: path("M7.5 17.5a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1");
}

.lovvf5btp {
  d: path("M10 7.75a.75.75 0 0 1 .75.75V10a.75.75 0 0 1-1.5 0V8.5a.75.75 0 0 1 .75-.75");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.u-kz_tbod {
  d: path("M8.775 1.538a1 1 0 0 1 .687 1.237l-1 3.5a1 1 0 1 1-1.924-.55l1-3.5a1 1 0 0 1 1.237-.687m0 16.924a1 1 0 0 0 .687-1.237l-1-3.5a1 1 0 1 0-1.924.55l1 3.5a1 1 0 0 0 1.237.687m2.45 0a1 1 0 0 1-.686-1.237l1-3.5a1 1 0 1 1 1.922.55l-1 3.5a1 1 0 0 1-1.236.687m0-16.924a1 1 0 0 0-.686 1.237l1 3.5a1 1 0 1 0 1.922-.55l-1-3.5a1 1 0 0 0-1.236-.687");
}

.wiele__nh {
  d: path("M12.25 10a.75.75 0 0 1-.75.75H10a.75.75 0 0 1 0-1.5h1.5a.75.75 0 0 1 .75.75M7.5 2.5a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1");
}

</style>
