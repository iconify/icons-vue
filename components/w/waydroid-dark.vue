<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imw09osfp.css';
import '../../css/n/n_03jgbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imw09osfp"/><path class="n_03jgbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:waydroid-dark" /></template>
