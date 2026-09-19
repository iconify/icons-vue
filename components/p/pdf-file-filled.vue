<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8s7p28am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t8s7p28am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pdf-file-filled" /></template>
