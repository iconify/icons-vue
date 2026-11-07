<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip0t-wb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip0t-wb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radar-2-linear" /></template>
