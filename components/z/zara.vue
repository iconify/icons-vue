<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re7s0bcpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re7s0bcpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zara" /></template>
