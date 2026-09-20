<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk9k9sdqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk9k9sdqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:payoneer" /></template>
