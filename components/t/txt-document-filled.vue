<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqrurlbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yqrurlbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:txt-document-filled" /></template>
