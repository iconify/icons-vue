<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amhd8z8lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amhd8z8lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tara" /></template>
