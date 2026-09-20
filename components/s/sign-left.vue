<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt74o3_bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt74o3_bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sign-left" /></template>
