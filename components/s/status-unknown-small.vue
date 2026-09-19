<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uedkzf-5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<rect class="uedkzf-5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:status-unknown-small" /></template>
