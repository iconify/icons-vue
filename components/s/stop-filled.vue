<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hidu3cdfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hidu3cdfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:stop-filled" /></template>
