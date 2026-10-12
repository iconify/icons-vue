<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvtbf90ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rvtbf90ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:stop-fill-20" /></template>
