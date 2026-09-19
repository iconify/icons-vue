<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwljtcb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwljtcb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:sun" /></template>
