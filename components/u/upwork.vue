<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p39nanrne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p39nanrne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:upwork" /></template>
