<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u41r5aczw.css';
import '../../css/u/umyvzfuaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u41r5aczw"/><path class="umyvzfuaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-mark-outline" /></template>
