<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt67l6e-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rt67l6e-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:more-vertical-fill" /></template>
