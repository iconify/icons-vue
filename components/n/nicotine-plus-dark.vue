<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-dxomgwz.css';
import '../../css/s/sj_lllbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b-dxomgwz"/><path class="sj_lllbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nicotine-plus-dark" /></template>
