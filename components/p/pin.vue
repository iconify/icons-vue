<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngt43k2ft.css';
import '../../css/h/hi1o7nsyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ngt43k2ft"/><path class="hi1o7nsyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pin" /></template>
