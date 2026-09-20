<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pis0eubmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pis0eubmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:playlist" /></template>
