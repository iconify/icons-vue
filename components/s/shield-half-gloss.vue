<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb6olbqax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb6olbqax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-half-gloss" /></template>
