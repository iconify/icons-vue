<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0un1obzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0un1obzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:play-forward-fill" /></template>
