<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp06kp_uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pp06kp_uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minus-square-filled" /></template>
