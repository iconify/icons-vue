<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhnnvfbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhnnvfbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:stop-filled" /></template>
