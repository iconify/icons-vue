<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/und3nmb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="und3nmb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:time" /></template>
