<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="krnjl9bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-down-48-regular" /></template>
<style>
.krnjl9bzi {
  fill: currentColor;
  d: path("M22.241 39.566c.652 1.238 2.422 1.248 3.088.017l15.954-29.501a1.75 1.75 0 0 0-1.54-2.583H8.256a1.75 1.75 0 0 0-1.549 2.565zm5.287 1.206c-1.617 2.99-5.915 2.966-7.499-.041L4.495 11.229C3.005 8.4 5.057 5 8.255 5h31.488c3.22 0 5.27 3.44 3.739 6.272z");
}

</style>
