<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pap4jeb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pap4jeb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:slug" /></template>
