<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yilbywqwu.css';
import '../../css/r/rgoffbnwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yilbywqwu"/><path class="rgoffbnwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openvas-light" /></template>
