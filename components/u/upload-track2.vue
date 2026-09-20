<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlhkeqbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zlhkeqbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:upload-track2" /></template>
