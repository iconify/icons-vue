<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs41k2b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs41k2b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-single-neutral-female-remix" /></template>
