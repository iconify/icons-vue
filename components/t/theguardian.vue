<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed943sbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed943sbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:theguardian" /></template>
