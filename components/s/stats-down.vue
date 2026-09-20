<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwimmtb7k.css';
import '../../css/w/wtjey9bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qwimmtb7k"/><path class="wtjey9bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:stats-down" /></template>
