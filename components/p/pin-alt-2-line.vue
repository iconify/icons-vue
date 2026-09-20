<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhqua-lqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhqua-lqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pin-alt-2-line" /></template>
