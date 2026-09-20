<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbbc3kb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbbc3kb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:visual-studio" /></template>
