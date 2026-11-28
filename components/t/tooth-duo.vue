<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in_f27l9g.css';
import '../../css/l/l-21abmhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in_f27l9g secondary"/><path class="l-21abmhq primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tooth-duo" /></template>
