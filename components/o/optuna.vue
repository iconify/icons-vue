<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2q460b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2q460b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:optuna" /></template>
