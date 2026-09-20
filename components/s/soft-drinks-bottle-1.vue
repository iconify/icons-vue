<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcb459bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcb459bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:soft-drinks-bottle-1" /></template>
