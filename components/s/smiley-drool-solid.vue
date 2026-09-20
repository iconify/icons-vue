<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un7b5bcgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="un7b5bcgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-drool-solid" /></template>
