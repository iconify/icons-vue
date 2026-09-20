<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miehgxb5z.css';
import '../../css/e/ekhn6xp0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miehgxb5z"/><path class="ekhn6xp0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:photo-album-2-line" /></template>
