<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-7j2m-uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-7j2m-uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:megaphone" /></template>
