<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6w-_kvsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t6w-_kvsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:valetudo-light" /></template>
