<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwqo_9cnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mwqo_9cnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:religion-cross-2-religion-cross-culture-thin-line" /></template>
