<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw55fhbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw55fhbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:presentation" /></template>
