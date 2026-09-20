<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ankggccnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ankggccnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:paint-bucket-accent" /></template>
