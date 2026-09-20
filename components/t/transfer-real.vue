<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp90ugwwx.css';
import '../../css/x/xli4t7b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pp90ugwwx"/><path class="xli4t7b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:transfer-real" /></template>
