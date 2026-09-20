<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkd3jjpvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gkd3jjpvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-4-remix" /></template>
