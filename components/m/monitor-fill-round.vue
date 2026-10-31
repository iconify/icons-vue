<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu4mob-9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu4mob-9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-fill-round" /></template>
