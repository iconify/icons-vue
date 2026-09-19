<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxrskd1xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxrskd1xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:share" /></template>
