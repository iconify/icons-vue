<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpg-7wb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gpg-7wb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:taurus" /></template>
