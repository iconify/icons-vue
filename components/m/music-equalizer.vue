<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6gt3bbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j6gt3bbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:music-equalizer" /></template>
