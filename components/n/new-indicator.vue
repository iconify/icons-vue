<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/razwxr_ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="razwxr_ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:new-indicator" /></template>
