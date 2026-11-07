<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkyfhubwr.css';
import '../../css/z/zyz94_b1d.css';
import '../../css/k/ksibtyk_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkyfhubwr"/><path class="zyz94_b1d"/><path class="ksibtyk_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-pen-bold" /></template>
