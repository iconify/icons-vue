<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp28bbubj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zp28bbubj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suspension-outline" /></template>
