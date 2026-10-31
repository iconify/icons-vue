<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phhi86ilx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phhi86ilx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-round" /></template>
