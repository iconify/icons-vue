<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf8d9fbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf8d9fbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-1-solid" /></template>
