<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj52scc1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="oj52scc1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-minus" /></template>
