<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdo6r1bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdo6r1bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:printer-fill" /></template>
