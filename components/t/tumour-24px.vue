<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f67187bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f67187bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:tumour-24px" /></template>
