<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqhb0gb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-user-fill-sharp" /></template>
<style>
.dqhb0gb6m {
  fill: currentColor;
  d: path("M15.47 20.217c-1.655 2.376-5.285 2.376-6.94 0a3.85 3.85 0 0 1-1.6.012c-2.155-.433-3.627-2.594-3.147-4.759c-2.376-1.655-2.376-5.285 0-6.94c-.617-2.786 1.961-5.364 4.747-4.747c1.655-2.376 5.285-2.376 6.94 0c2.786-.617 5.364 1.961 4.747 4.747c2.376 1.655 2.376 5.285 0 6.94c.48 2.165-.992 4.326-3.147 4.759a3.85 3.85 0 0 1-1.6-.012M9.236 7.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M6.17 17.574c.609.716 1.544.932 2.399.524c.255-.122.55-.13.812-.023c.245.101.44.296.542.54A2.205 2.205 0 0 0 12 20c.931 0 1.718-.525 2.077-1.385a1 1 0 0 1 1.354-.517c.855.408 1.79.192 2.399-.524A6 6 0 0 0 12.003 13a6.01 6.01 0 0 0-5.833 4.574");
}

</style>
