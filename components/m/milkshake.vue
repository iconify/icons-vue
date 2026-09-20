<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruwtz7ztn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruwtz7ztn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:milkshake" /></template>
