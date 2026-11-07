<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riv2d9n9z.css';
import '../../css/j/j10j52bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="riv2d9n9z"/><path class="j10j52bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-off-outline" /></template>
