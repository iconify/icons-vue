<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmggm0vav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmggm0vav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:microscope-filled" /></template>
