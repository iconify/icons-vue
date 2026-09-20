<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z37mi_bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z37mi_bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-basket-fill" /></template>
