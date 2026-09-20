<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8qsyfp5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8qsyfp5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:netdata" /></template>
