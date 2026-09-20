<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dse2v6b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dse2v6b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:video-file-filled" /></template>
