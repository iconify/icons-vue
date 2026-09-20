<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2fiuw9jr.css';
import '../../css/k/koneki24a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2fiuw9jr"/><path clip-rule="evenodd" class="koneki24a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tag-2-fill" /></template>
