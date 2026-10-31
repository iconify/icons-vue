<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_3ma80au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_3ma80au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-fill-round" /></template>
