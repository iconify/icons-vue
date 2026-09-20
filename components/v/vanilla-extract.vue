<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5yhegb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5yhegb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vanilla-extract" /></template>
