<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxf_lxb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxf_lxb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-twice-square-bold" /></template>
