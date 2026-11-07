<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb-xa_zrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cb-xa_zrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shop-outline" /></template>
