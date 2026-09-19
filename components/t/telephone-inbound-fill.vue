<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiok6x51q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uiok6x51q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:telephone-inbound-fill" /></template>
