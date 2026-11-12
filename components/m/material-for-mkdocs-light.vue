<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6-lcumwc.css';
import '../../css/l/lvu082s3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j6-lcumwc"/><path class="lvu082s3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:material-for-mkdocs-light" /></template>
