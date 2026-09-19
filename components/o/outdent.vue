<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocb0_hbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="ocb0_hbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:outdent" /></template>
