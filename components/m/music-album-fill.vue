<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa2qbuzpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa2qbuzpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:music-album-fill" /></template>
