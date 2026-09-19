<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkey5szpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkey5szpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:paragraph-bullets-point-01" /></template>
