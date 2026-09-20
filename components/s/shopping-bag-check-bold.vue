<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu2tw4bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu2tw4bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shopping-bag-check-bold" /></template>
