<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydbw2o_ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ydbw2o_ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:upload-file-remix" /></template>
