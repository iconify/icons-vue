<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfh1tlbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfh1tlbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:waves-electricity" /></template>
