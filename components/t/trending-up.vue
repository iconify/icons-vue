<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvaa8ubcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="jvaa8ubcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:trending-up" /></template>
