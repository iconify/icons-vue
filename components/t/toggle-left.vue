<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scxwqkb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scxwqkb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:toggle-left" /></template>
