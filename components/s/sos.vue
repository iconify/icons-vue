<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esrh2-sil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="esrh2-sil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:sos" /></template>
