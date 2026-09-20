<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvqop6bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvqop6bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-orientation" /></template>
