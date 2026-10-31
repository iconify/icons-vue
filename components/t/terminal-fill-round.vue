<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rls14db7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rls14db7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:terminal-fill-round" /></template>
