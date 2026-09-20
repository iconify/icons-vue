<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qws1l074c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qws1l074c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tube-light-left-light-right" /></template>
