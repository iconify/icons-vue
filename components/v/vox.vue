<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yedb5g6ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yedb5g6ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vox" /></template>
