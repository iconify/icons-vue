<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrv1b1bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrv1b1bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:skip-up-line" /></template>
