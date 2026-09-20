<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8mx9__7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s8mx9__7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:open-new-filled" /></template>
