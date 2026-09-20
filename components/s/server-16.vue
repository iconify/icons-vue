<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_n3habvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y_n3habvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:server-16" /></template>
