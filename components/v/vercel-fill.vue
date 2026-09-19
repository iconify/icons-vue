<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akipomtzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akipomtzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:vercel-fill" /></template>
