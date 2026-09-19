<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld5kc0m-n.css';
import '../../css/b/bblqfdb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ld5kc0m-n"/><path class="bblqfdb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-back-circle-outline" /></template>
