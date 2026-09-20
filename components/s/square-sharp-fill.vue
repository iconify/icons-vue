<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i000l1xee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i000l1xee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-sharp-fill" /></template>
