<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g51izkbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g51izkbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sprout" /></template>
