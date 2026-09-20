<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9_h0wb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z9_h0wb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-level-off-solid" /></template>
