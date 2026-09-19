<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzj8srv2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uzj8srv2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:play-back-sharp" /></template>
