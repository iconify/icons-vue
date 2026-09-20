<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2qg2dbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="v2qg2dbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:medium" /></template>
