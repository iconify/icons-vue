<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbma3xpbl.css';
import '../../css/a/avpyb3bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbma3xpbl"/><path class="avpyb3bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-pen-filled" /></template>
