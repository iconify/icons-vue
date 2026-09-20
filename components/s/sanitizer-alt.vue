<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyt55ki0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyt55ki0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sanitizer-alt" /></template>
