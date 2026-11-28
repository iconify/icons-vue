<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb7-g2b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb7-g2b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sticky-note-plus" /></template>
