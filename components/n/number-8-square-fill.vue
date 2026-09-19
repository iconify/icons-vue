<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnox6ln0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnox6ln0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-8-square-fill" /></template>
