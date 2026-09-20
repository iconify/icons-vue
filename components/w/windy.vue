<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq41ncb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq41ncb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:windy" /></template>
