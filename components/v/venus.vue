<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksbr4pb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksbr4pb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:venus" /></template>
