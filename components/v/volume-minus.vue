<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj88e2lso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj88e2lso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:volume-minus" /></template>
