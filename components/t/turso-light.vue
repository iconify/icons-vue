<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc_mx6bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":201,"height":170};
const content = `<path class="bc_mx6bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:turso-light" /></template>
