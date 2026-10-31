<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiesi5b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiesi5b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spotify-fill-round" /></template>
