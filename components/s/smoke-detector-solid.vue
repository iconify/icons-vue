<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za9unubkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="za9unubkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smoke-detector-solid" /></template>
