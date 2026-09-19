<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe3cn1bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe3cn1bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:radio-circle" /></template>
