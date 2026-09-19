<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk01hcbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":691};
const content = `<path class="nk01hcbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:vertical" /></template>
