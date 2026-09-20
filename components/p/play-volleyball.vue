<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u82pom1na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u82pom1na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-volleyball" /></template>
