<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzeah-msh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zzeah-msh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-west-circle-fill" /></template>
