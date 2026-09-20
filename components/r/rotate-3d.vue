<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq4wbcy9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq4wbcy9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rotate-3d" /></template>
