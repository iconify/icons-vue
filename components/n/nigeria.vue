<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl8-tdb0a.css';
import '../../css/l/l9cl-boot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="tl8-tdb0a"/><path class="l9cl-boot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:nigeria" /></template>
