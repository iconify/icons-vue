<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckex8b9yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckex8b9yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-basket-sharp" /></template>
