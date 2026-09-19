<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8o1-8brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j8o1-8brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:risc-v" /></template>
