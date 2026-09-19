<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf6kgxbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf6kgxbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:volume" /></template>
