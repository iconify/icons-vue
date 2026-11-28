<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzzepkb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uzzepkb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-close-thin" /></template>
