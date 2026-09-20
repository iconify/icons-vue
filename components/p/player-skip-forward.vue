<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giu7wm7zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giu7wm7zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-skip-forward" /></template>
