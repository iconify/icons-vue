<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ozvdb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:picnic-blanket" /></template>
<style>
.g-ozvdb4z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.581 5.081Q6.021 6.64 5.79 8.75H4.5q-.932 0-1.591.659T2.25 11t.659 1.591q.421.421.952.573l.652 3.474v.001l.75 3.999q.012.064.035.125t.056.117t.075.106t.092.091q.05.042.107.074t.117.054q.062.023.126.034T6 21.25h12q.065 0 .129-.011t.126-.034q.061-.022.117-.054t.107-.074t.092-.091t.075-.106t.056-.117q.023-.061.035-.125l.75-3.999v-.002l.652-3.473q.531-.152.952-.573q.659-.659.659-1.591q0-2.25-2.25-2.25h-1.29q-.231-2.11-1.791-3.669Q14.589 3.25 12 3.25T7.581 5.081M18.128 15.75H5.872l-.468-2.5h13.192zm-11.974 1.5h11.692l-.468 2.5H6.622zM8.641 6.141Q7.523 7.259 7.304 8.75h9.392q-.219-1.491-1.337-2.609Q13.968 4.75 12 4.75T8.641 6.141");
}

</style>
