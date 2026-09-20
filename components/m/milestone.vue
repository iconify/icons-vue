<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zregm3blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zregm3blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:milestone" /></template>
