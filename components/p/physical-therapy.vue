<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qflhlgwkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qflhlgwkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:physical-therapy" /></template>
