<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpdbnghdn.css';
import '../../css/w/wv9ep6bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hpdbnghdn"/><path class="wv9ep6bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:rocket" /></template>
