<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk-qwvomb.css';
import '../../css/j/jfe6ttbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bk-qwvomb"/><path class="jfe6ttbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:penn-state-nittany-lions" /></template>
