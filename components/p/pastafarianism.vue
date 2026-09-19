<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekbxqslqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ekbxqslqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pastafarianism" /></template>
