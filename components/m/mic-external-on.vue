<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftu1qlbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mic-external-on" /></template>
<style>
.ftu1qlbnr {
  fill: currentColor;
  d: path("M5.416 7.462q-.26-.33-.396-.714q-.135-.385-.135-.787q0-1.041.728-1.77q.729-.73 1.77-.73t1.77.73t.732 1.77q0 .402-.136.787q-.135.385-.395.713zm4.778 13.077q-1.363 0-2.336-.972t-.973-2.336h-.77l-.884-8.692h4.308l-.885 8.692h-.77q0 .96.675 1.634q.674.674 1.633.674q.96 0 1.634-.678t.674-1.63V6.769q0-1.364.971-2.336t2.335-.972t2.336.972q.974.972.974 2.336v13.77h-1V6.768q0-.952-.675-1.63q-.674-.678-1.633-.678q-.96 0-1.634.678T13.5 6.77v10.462q0 1.364-.971 2.336t-2.335.971");
}

</style>
