<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj14t89gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lj14t89gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:paperclip-solid" /></template>
