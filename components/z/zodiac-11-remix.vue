<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2_nfc4uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c2_nfc4uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-11-remix" /></template>
