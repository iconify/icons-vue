<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-4pk2b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-4pk2b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mg" /></template>
