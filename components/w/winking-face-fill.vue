<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh99y8bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mh99y8bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:winking-face-fill" /></template>
