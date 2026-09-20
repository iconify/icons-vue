<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe80l4_cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xe80l4_cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:module-puzzle-1-solid" /></template>
