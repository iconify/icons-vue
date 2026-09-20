<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm_ni9ugb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm_ni9ugb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-f4-filled" /></template>
