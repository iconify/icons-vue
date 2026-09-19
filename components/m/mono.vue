<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp3q74byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qp3q74byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mono" /></template>
