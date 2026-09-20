<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnmf49kpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnmf49kpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:postman" /></template>
