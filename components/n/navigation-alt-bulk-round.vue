<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spj17bciu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spj17bciu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-alt-bulk-round" /></template>
