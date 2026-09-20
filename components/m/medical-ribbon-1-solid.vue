<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vca59qbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vca59qbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:medical-ribbon-1-solid" /></template>
