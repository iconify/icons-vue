<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgsy0ccso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgsy0ccso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-in-up-sharp" /></template>
