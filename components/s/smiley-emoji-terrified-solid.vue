<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8irvcxoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p8irvcxoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-emoji-terrified-solid" /></template>
