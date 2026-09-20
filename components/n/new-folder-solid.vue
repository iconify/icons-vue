<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmgot2wmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cmgot2wmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:new-folder-solid" /></template>
