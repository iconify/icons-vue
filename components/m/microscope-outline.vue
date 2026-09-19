<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aok5afb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aok5afb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:microscope-outline" /></template>
