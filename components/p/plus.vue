<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntat1nopg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ntat1nopg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:plus" /></template>
