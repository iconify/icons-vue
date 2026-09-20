<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqzuu5bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rqzuu5bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:telescope-radio" /></template>
