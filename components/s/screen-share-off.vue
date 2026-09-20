<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meh55mbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meh55mbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:screen-share-off" /></template>
