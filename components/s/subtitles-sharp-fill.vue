<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqbzs7b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hqbzs7b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:subtitles-sharp-fill" /></template>
