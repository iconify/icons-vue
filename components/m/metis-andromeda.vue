<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr1jnvb_y.css';
import '../../css/u/umd4-qbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr1jnvb_y"/><path class="umd4-qbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:metis-andromeda" /></template>
