<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih3jvg44a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih3jvg44a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:visa" /></template>
