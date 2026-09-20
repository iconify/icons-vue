<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4utxthcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4utxthcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-bold" /></template>
