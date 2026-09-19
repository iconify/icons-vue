<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovmyto5xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ovmyto5xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:supersonic-bullet" /></template>
