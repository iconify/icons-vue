<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dolkt7wiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dolkt7wiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tools-kitchen-2-filled" /></template>
