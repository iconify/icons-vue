<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg1q65bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kg1q65bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-cute-solid" /></template>
