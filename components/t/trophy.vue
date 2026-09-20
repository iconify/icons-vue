<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw3f1ccle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mw3f1ccle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:trophy" /></template>
