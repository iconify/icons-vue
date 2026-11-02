<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x16vlc8os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x16vlc8os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:planet-fill" /></template>
