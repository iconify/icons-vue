<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_r-cv1uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_r-cv1uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:umbrella-sharp" /></template>
