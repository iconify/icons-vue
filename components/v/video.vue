<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0o9u5blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w0o9u5blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:video" /></template>
