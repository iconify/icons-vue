<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1j9atx_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="b1j9atx_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:waste-basket-10" /></template>
