<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lal5kjbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lal5kjbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ubisoft-logo-solid" /></template>
