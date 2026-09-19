<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-c8q9x4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-c8q9x4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:video" /></template>
