<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uio9qibqb.css';
import '../../css/j/jcy41ac7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="uio9qibqb"/><path class="jcy41ac7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:richy" /></template>
