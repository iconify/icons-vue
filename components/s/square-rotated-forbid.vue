<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g74y0wb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g74y0wb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rotated-forbid" /></template>
