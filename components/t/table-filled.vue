<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws4zpwkgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws4zpwkgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-filled" /></template>
