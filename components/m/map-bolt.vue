<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m297bkbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m297bkbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-bolt" /></template>
