<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jci4y6a-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jci4y6a-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:trash-alt" /></template>
