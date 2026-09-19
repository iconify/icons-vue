<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prlgct3cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="prlgct3cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:video-solid" /></template>
