<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzo83b3uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzo83b3uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pencil-ruler" /></template>
