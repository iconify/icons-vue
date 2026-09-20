<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k23o32d_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k23o32d_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:make-up-brush-solid" /></template>
