<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h812qk4ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h812qk4ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wand-off" /></template>
