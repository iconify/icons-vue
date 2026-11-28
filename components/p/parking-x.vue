<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4wixbk7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4wixbk7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:parking-x" /></template>
