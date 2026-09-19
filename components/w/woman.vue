<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kynfmmbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="kynfmmbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:woman" /></template>
