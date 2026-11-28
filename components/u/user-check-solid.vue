<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzt8uf4ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzt8uf4ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-check-solid" /></template>
