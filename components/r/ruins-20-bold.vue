<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfoxxnbix.css';
import '../../css/y/yhs2jn2-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yfoxxnbix"/><path class="yhs2jn2-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ruins-20-bold" /></template>
