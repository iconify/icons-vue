<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/temo6clri.css';
import '../../css/j/j052408uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="temo6clri"/><path class="j052408uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:tablet-portrait" /></template>
