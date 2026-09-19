<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7nc_vb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="s7nc_vb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tooth" /></template>
