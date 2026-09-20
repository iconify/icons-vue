<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfac9mbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfac9mbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pandoc" /></template>
