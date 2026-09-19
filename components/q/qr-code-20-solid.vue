<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe0pevbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pe0pevbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:qr-code-20-solid" /></template>
