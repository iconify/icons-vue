<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo-otpdts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo-otpdts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:shopping-cart" /></template>
