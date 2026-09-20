<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy7ovob3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy7ovob3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shopping-basket-2-solid" /></template>
