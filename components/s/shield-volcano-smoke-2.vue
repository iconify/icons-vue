<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc7aas1aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rc7aas1aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:shield-volcano-smoke-2" /></template>
