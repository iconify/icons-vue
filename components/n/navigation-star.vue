<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhjk0pbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhjk0pbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-star" /></template>
