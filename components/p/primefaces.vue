<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb_q9yb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb_q9yb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:primefaces" /></template>
