<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny2g-5bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny2g-5bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:more-horizontal" /></template>
