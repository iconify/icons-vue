<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1fr8ybcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u1fr8ybcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:vr-headset-2-solid" /></template>
