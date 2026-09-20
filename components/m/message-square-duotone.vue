<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps6co1fpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps6co1fpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-duotone" /></template>
