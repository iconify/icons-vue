<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3kld2boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3kld2boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-arrow-right" /></template>
