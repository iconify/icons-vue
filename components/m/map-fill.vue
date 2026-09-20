<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzko38s9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzko38s9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-fill" /></template>
