<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn06cubph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn06cubph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stars-a" /></template>
