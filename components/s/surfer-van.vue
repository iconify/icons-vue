<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b49aw6bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b49aw6bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:surfer-van" /></template>
