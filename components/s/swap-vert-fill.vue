<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbibiqwmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbibiqwmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:swap-vert-fill" /></template>
