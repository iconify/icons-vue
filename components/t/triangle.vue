<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8u8d-z0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="x8u8d-z0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:triangle" /></template>
