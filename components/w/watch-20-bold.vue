<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8tbbbvzb.css';
import '../../css/v/vanfr9l2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q8tbbbvzb"/><path class="vanfr9l2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:watch-20-bold" /></template>
