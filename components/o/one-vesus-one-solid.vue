<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny29n5mmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ny29n5mmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:one-vesus-one-solid" /></template>
