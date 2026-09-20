<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn_7ebboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_7ebboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:skip-back-sharp" /></template>
