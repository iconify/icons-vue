<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hom_m1b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hom_m1b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sun-2-outline" /></template>
