<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f38qgjqtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:menstrual-health-outline-rounded" /></template>
<style>
.f38qgjqtp {
  fill: currentColor;
  d: path("M8.494 20.29q-1.642-.711-2.858-1.926q-1.215-1.216-1.926-2.858T3 12V6.115q0-.51.444-.726t.848.08l4.066 3.056q.611-1.002 1.335-2.056t1.598-2.146q.286-.362.709-.352t.71.352q.854 1.093 1.587 2.134q.734 1.041 1.345 2.068l4.066-3.056q.404-.298.848-.08t.444.726V12q0 1.864-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21t-3.506-.71M6 15q0-1.136.463-2.553q.462-1.416 1.378-3.062L4 6.5V12q0 1.908.845 3.507t2.269 2.628q-.512-.635-.813-1.43T6 15m9.538 3.538Q17 17.075 17 15q0-1.766-1.308-4.454Q14.385 7.858 12 5q-2.384 2.87-3.692 5.552Q7 13.235 7 15q0 2.075 1.463 3.538T12 20t3.538-1.463M18 15q0 .91-.301 1.705t-.812 1.43q1.423-1.03 2.268-2.628T20 12V6.5l-3.84 2.879q.915 1.646 1.378 3.062Q18 13.858 18 15");
}

</style>
