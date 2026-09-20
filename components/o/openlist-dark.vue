<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy2y_xbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xy2y_xbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openlist-dark" /></template>
