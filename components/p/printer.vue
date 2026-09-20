<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7kbl7nxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7kbl7nxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:printer" /></template>
