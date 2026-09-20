<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqflpkaqy.css';
import '../../css/v/vcu56-q6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqflpkaqy"/><path class="vcu56-q6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:podcast-duotone" /></template>
