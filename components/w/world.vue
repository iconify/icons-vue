<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckny4dw-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckny4dw-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:world" /></template>
