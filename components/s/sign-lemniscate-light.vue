<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmlc81trv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmlc81trv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-lemniscate-light" /></template>
