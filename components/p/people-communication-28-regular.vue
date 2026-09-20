<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="e392kebwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-communication-28-regular" /></template>
<style>
.e392kebwh {
  fill: currentColor;
  d: path("M15.403 15.904a6.5 6.5 0 0 1 9.193 9.193a.75.75 0 0 1-1.06-1.06a5 5 0 1 0-7.072 0a.75.75 0 0 1-1.06 1.06a6.5 6.5 0 0 1 0-9.193m1.768 1.768a4 4 0 1 1 5.656 5.657a.75.75 0 0 1-1.06-1.061a2.5 2.5 0 1 0-3.536 0a.751.751 0 0 1-1.06 1.061a4 4 0 0 1 0-5.657m-2.276-2.665c-.475.44-.89.943-1.238 1.493H4.25a.75.75 0 0 0-.75.75v.495l.001.018q.001.03.008.1c.01.094.03.235.074.409c.087.347.261.812.61 1.278c.673.897 2.115 1.95 5.307 1.95c1.262 0 2.25-.168 3.024-.422q.061.77.266 1.488c-.902.27-1.987.434-3.29.434c-3.558 0-5.491-1.197-6.506-2.55a5.1 5.1 0 0 1-.866-1.815a4.5 4.5 0 0 1-.125-.797L2 17.78v-.531A2.25 2.25 0 0 1 4.25 15h10.5q.073.001.145.007M9.5 4a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M20 6a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M9.5 5.5a3 3 0 1 0 0 6a3 3 0 0 0 0-6m10.5 2a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
