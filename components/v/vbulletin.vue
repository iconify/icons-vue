<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6ur09q4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6ur09q4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vbulletin" /></template>
