<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra9-jw9gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra9-jw9gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-bold" /></template>
