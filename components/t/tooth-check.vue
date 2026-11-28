<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqg9f2beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqg9f2beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tooth-check" /></template>
