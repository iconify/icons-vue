<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxx_4tbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxx_4tbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stairs" /></template>
