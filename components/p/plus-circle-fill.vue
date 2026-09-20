<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1s7b7bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1s7b7bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:plus-circle-fill" /></template>
