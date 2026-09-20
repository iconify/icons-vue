<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fah1b-_sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fah1b-_sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-10-solid" /></template>
