<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w9r60ybwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-shield-20-filled" /></template>
<style>
.w9r60ybwy {
  fill: currentColor;
  d: path("M15.12 10.963a.574.574 0 0 1 .76 0c.509.484 1.484 1.254 2.684 1.412c.239.032.436.212.436.438v2.11c0 2.839-2.783 3.87-3.386 4.06a.37.37 0 0 1-.227 0c-.602-.19-3.387-1.22-3.387-4.06v-2.11c0-.226.197-.407.437-.438c1.199-.158 2.175-.928 2.682-1.412M7.37 3.556c1.14-2.074 4.12-2.074 5.259 0l3.515 6.4a1.58 1.58 0 0 0-1.6.185l-.115.098c-.432.411-1.147.955-1.96 1.117l-.269.045c-.531.111-1.116.54-1.192 1.254l-.008.157v2.112c0 1.319.484 2.331 1.111 3.08H4.504c-2.281 0-3.727-2.444-2.629-4.443zM10 12.75a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m0-6.25a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 1 0V7a.5.5 0 0 0-.5-.5");
}

</style>
