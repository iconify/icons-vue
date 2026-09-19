<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbj_h5bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="wbj_h5bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:simplenote" /></template>
