<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh2bt7bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh2bt7bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-g-filled" /></template>
