<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3ho21jte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3ho21jte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:oasys" /></template>
