<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl_vkh67w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl_vkh67w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:stg" /></template>
