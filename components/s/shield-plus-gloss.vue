<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9whgvyqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9whgvyqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-plus-gloss" /></template>
