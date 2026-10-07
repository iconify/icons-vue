<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l88hrmbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l88hrmbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:replace" /></template>
