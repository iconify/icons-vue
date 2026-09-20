<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc2r8v-9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc2r8v-9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:media-record" /></template>
