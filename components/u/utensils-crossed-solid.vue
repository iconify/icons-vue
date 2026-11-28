<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx5hbbb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx5hbbb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:utensils-crossed-solid" /></template>
