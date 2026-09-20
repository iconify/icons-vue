<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oss2782tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oss2782tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:table-settings" /></template>
