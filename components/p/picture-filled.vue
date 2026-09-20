<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i68crsbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i68crsbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:picture-filled" /></template>
