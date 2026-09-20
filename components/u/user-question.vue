<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foed28bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foed28bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-question" /></template>
