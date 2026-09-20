<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-3ir0g2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-3ir0g2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mojeek" /></template>
