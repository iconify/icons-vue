<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap95lub3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap95lub3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vector-bezier-circle" /></template>
