<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmnd63bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmnd63bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:notebook" /></template>
