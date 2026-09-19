<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yre9_ib2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yre9_ib2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:progress-old" /></template>
