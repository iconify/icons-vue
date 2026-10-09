<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qthvhvbbw.css';
import '../../css/s/swgrbdc6r.css';
import '../../css/o/o5prfsbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qthvhvbbw"/><path class="swgrbdc6r"/><path class="o5prfsbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sleet-48" /></template>
