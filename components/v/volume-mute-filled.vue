<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9o6g8dcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v9o6g8dcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:volume-mute-filled" /></template>
