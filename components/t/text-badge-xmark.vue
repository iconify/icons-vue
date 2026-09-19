<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc9wtibdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lc9wtibdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-badge-xmark" /></template>
