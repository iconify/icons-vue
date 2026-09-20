<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfjkhxaub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfjkhxaub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:picture-in-picture-top-right-outline" /></template>
