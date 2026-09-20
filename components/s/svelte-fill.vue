<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2ny02bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2ny02bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:svelte-fill" /></template>
