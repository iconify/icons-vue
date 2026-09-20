<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpmqhyrux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vpmqhyrux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-logo-block" /></template>
