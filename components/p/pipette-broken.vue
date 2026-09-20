<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jicenlb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jicenlb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pipette-broken" /></template>
