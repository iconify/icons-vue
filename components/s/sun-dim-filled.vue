<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-vkei2jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-vkei2jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sun-dim-filled" /></template>
