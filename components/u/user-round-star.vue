<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd6cbnbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd6cbnbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-round-star" /></template>
