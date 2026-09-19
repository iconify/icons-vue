<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k22iu-b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k22iu-b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:usb-key" /></template>
