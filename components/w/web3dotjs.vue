<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvvrx4bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvvrx4bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:web3dotjs" /></template>
