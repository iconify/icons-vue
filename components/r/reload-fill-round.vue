<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jayktdbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jayktdbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reload-fill-round" /></template>
