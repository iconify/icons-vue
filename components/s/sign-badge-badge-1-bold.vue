<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cga-xtbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cga-xtbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:sign-badge-badge-1-bold" /></template>
