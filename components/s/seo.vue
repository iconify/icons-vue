<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7_xhfb5l.css';
import '../../css/f/f_1_8rbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k7_xhfb5l"/><path class="f_1_8rbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:seo" /></template>
