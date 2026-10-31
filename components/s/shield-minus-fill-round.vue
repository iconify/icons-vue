<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed-kn0bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed-kn0bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-minus-fill-round" /></template>
