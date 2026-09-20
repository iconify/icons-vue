<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt-2uw01i.css';
import '../../css/c/clcbemb9z.css';
import '../../css/z/zqkur5bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qt-2uw01i"/><path class="clcbemb9z"/><path class="zqkur5bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mkvpriority" /></template>
