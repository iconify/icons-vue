<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz-3-qpad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zz-3-qpad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nurse-female" /></template>
