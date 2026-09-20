<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nku-_zb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nku-_zb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:zoom-document-solid" /></template>
