<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxj3gjb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxj3gjb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:netim" /></template>
