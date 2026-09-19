<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1x2-08ga.css';
import '../../css/z/zzq0s9bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t1x2-08ga"/><path class="zzq0s9bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:trash-b" /></template>
