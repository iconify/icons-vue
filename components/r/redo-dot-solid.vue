<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anb5yxb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anb5yxb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:redo-dot-solid" /></template>
