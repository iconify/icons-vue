<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei5tqekdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":460,"height":512};
const content = `<path class="ei5tqekdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:stdlibjs" /></template>
