<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2g82w44d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2g82w44d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-heart" /></template>
