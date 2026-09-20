<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdlsigbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bdlsigbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:monument" /></template>
