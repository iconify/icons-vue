<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcvnjobls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcvnjobls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:track-prev" /></template>
