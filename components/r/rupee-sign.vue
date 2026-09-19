<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b06mc9r6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="b06mc9r6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:rupee-sign" /></template>
