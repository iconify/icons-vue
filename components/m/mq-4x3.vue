<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuy3_33xc.css';
import '../../css/p/p3uaq9bss.css';
import '../../css/a/a4ahv-08i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="wuy3_33xc"/><path class="p3uaq9bss"/><path class="a4ahv-08i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mq-4x3" /></template>
