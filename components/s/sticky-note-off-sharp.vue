<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l300hsomo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l300hsomo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-off-sharp" /></template>
