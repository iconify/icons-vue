<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm40gt1ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hm40gt1ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plusminus" /></template>
