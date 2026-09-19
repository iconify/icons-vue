<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k44ryia2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k44ryia2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:printer-3d" /></template>
