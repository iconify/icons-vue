<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_7jbxxkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_7jbxxkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-7-solid" /></template>
