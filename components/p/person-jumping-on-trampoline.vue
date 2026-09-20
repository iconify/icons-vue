<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0xxf5bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m0xxf5bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-jumping-on-trampoline" /></template>
