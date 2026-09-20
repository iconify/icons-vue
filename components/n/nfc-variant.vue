<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9x5jkb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9x5jkb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:nfc-variant" /></template>
