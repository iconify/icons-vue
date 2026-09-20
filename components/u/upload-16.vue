<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-tx9_o5y.css';
import '../../css/l/l3l94kbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h-tx9_o5y"/><path class="l3l94kbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:upload-16" /></template>
