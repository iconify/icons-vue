<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh01xib5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh01xib5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:zap-square" /></template>
