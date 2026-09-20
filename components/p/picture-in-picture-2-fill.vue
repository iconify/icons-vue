<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gompo24de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gompo24de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:picture-in-picture-2-fill" /></template>
