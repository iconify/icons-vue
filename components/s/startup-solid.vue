<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-c7mbbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a-c7mbbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:startup-solid" /></template>
