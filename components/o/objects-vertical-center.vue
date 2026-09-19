<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjw8wvbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjw8wvbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:objects-vertical-center" /></template>
