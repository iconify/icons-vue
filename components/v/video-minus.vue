<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2fk9bu9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2fk9bu9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:video-minus" /></template>
