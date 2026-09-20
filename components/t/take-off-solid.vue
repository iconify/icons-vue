<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5_zc8bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z5_zc8bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:take-off-solid" /></template>
