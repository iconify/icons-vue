<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eofb2ccfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eofb2ccfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:panzerfaust" /></template>
