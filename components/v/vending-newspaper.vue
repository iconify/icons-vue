<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/attlt2bak.css';
import '../../css/w/w5pegf6wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="attlt2bak"/><path class="w5pegf6wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:vending-newspaper" /></template>
