<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmk_yopdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="xmk_yopdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:reademail" /></template>
