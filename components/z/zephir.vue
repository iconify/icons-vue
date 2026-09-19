<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zku74vjzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zku74vjzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:zephir" /></template>
