<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb28gsi8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xb28gsi8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:straight-cap-remix" /></template>
