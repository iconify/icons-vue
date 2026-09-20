<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df1sefjfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="df1sefjfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:phone" /></template>
