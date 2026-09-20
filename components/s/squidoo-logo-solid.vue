<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyj-1nb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zyj-1nb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:squidoo-logo-solid" /></template>
