<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf027v8gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zf027v8gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yugabytedb-dark" /></template>
