<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s06ujyb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s06ujyb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-bulk-round" /></template>
