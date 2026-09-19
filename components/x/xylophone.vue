<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzt7ai2sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzt7ai2sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:xylophone" /></template>
