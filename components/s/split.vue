<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coxm8-_zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coxm8-_zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:split" /></template>
