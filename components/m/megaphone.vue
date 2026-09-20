<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpby05bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpby05bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:megaphone" /></template>
