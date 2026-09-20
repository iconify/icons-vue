<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbu526_yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-thermostat-sensor" /></template>
<style>
.xbu526_yn {
  fill: currentColor;
  d: path("M12 21q-1.868 0-3.51-.708t-2.857-1.924t-1.924-2.856T3 12.003t.709-3.51t1.924-2.859T8.49 3.709T12 3q1.8 0 3.387.668t2.795 1.825t1.952 2.724t.847 3.36q-.577-.325-1.2-.499t-1.281-.174q-.505 0-.984.094q-.48.094-.931.283q-.168-.965-.755-1.566q-.588-.6-1.488-.6q-1.067 0-1.672.824T12.066 12q0 1.008.407 1.74q.408.731 1.135 1.004q-.061.287-.104.582q-.042.296-.042.616q0 1.283.6 2.411t1.702 1.826q-.881.408-1.838.614T12 21m1.86-6.994q-.466-.193-.734-.697q-.268-.503-.268-1.309q0-.927.4-1.518t1.09-.591q.644 0 1.025.493q.38.495.45 1.281q-.658.408-1.164 1.007q-.507.6-.8 1.334M18.5 19.98q-1.673 0-2.856-1.179t-1.183-2.86t1.183-2.86t2.856-1.178t2.856 1.179q1.182 1.178 1.182 2.86t-1.182 2.859T18.5 19.98M8.36 14.884l2.661-4.697v-.908H7.396v.775h2.735l.03.075l-2.495 4.352z");
}

</style>
