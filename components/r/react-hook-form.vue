<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjqq2vzds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjqq2vzds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:react-hook-form" /></template>
