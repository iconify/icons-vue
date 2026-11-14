<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozde0bblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozde0bblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:skoda-2026-long" /></template>
