<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snt7n62gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snt7n62gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:webassembly" /></template>
