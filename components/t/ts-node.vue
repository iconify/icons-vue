<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcgv1r9pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcgv1r9pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ts-node" /></template>
