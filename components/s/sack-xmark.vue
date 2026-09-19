<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/busg1jzlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="busg1jzlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:sack-xmark" /></template>
