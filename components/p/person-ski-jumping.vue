<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8pxs_baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f8pxs_baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-ski-jumping" /></template>
