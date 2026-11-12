<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3l_n81lx.css';
import '../../css/u/ubgppxb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3l_n81lx"/><path class="ubgppxb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oak-identity-dark" /></template>
