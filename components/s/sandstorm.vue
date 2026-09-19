<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl_5jt7fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kl_5jt7fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sandstorm" /></template>
