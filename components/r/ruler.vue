<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd6nirbah.css';
import '../../css/y/yjey4tfxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nd6nirbah"/><path class="yjey4tfxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:ruler" /></template>
