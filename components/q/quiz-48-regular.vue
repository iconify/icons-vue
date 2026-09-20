<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qywdb2bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-48-regular" /></template>
<style>
.qywdb2bsu {
  fill: currentColor;
  d: path("M35.75 6A6.25 6.25 0 0 1 42 12.25v23.5A6.25 6.25 0 0 1 35.75 42h-23.5A6.25 6.25 0 0 1 6 35.75v-23.5A6.25 6.25 0 0 1 12.25 6zm-23.5 2.5a3.75 3.75 0 0 0-3.75 3.75v23.5a3.75 3.75 0 0 0 3.75 3.75h23.5a3.75 3.75 0 0 0 3.75-3.75v-23.5a3.75 3.75 0 0 0-3.75-3.75zm6.026 25.501H35.75a1.25 1.25 0 1 1 0 2.5H17.742l-.018-.001H12.25a1.25 1.25 0 0 1 0-2.5h6.008zm5.244-6.005h12.23a1.25 1.25 0 1 1 0 2.5h-23.5a1.25 1.25 0 1 1 0-2.5h11.272zm-4.022-16.998c.506 0 .962.306 1.155.774l4.752 11.505a1.25 1.25 0 1 1-2.31.954l-.708-1.713h-5.775l-.707 1.713a1.25 1.25 0 1 1-2.31-.954l4.748-11.506a1.25 1.25 0 0 1 1.155-.773m12.25 0c.69 0 1.25.56 1.25 1.25V15h2.752a1.25 1.25 0 1 1 0 2.5h-2.752v2.748a1.25 1.25 0 0 1-2.5 0V17.5H27.75a1.25 1.25 0 0 1 0-2.5h2.748v-2.752c0-.69.56-1.25 1.25-1.25m-14.104 9.02h3.71l-1.856-4.494z");
}

</style>
