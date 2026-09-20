<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnnmw2ayq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qnnmw2ayq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:restaurant" /></template>
