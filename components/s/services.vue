<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wabg6tf_x.css';
import '../../css/c/ck9b5hbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wabg6tf_x"/><path class="ck9b5hbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:services" /></template>
