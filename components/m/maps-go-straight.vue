<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lawl0y4tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lawl0y4tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:maps-go-straight" /></template>
