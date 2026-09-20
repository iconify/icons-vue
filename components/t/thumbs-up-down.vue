<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feo0r_n-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feo0r_n-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thumbs-up-down" /></template>
