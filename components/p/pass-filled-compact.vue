<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgpd84i-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tgpd84i-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:pass-filled-compact" /></template>
