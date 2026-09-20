<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k84s8obrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k84s8obrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-check-sharp" /></template>
