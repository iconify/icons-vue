<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rib8vw59i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rib8vw59i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:triangle-exclamation" /></template>
