<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbpw3ccwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":7,"height":16};
const content = `<path class="wbpw3ccwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:plus-small" /></template>
