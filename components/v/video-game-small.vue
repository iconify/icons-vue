<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to43pubzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="to43pubzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:video-game-small" /></template>
