<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd83idj5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qd83idj5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:shortcode" /></template>
