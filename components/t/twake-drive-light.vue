<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qumyb9bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qumyb9bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twake-drive-light" /></template>
