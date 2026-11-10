<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drq0v9xaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drq0v9xaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-exclamation" /></template>
