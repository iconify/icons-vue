<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3kaikb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3kaikb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-user-fill-round" /></template>
