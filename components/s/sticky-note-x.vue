<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9w3eib8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9w3eib8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-x" /></template>
