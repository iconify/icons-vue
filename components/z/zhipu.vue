<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuo_d6bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuo_d6bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zhipu" /></template>
