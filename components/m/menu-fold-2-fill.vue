<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6xkasbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6xkasbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-fold-2-fill" /></template>
