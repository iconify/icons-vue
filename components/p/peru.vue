<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1fo9snfu.css';
import '../../css/l/l9cl-boot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="g1fo9snfu"/><path class="l9cl-boot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:peru" /></template>
