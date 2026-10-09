<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1rxfewyg.css';
import '../../css/f/fx_ekx88i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x1rxfewyg"/><path class="fx_ekx88i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:video-off-20" /></template>
