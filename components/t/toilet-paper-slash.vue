<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-0lb3bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="p-0lb3bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:toilet-paper-slash" /></template>
