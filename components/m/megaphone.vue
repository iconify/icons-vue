<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnv_ckbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cnv_ckbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:megaphone" /></template>
