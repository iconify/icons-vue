<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm8hnqbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qm8hnqbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:rectangle-one" /></template>
