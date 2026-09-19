<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw1cz0bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw1cz0bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:zap" /></template>
