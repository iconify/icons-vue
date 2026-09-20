<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlrsj2b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qlrsj2b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:passport-solid" /></template>
