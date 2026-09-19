<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz5dirmwx.css';
import '../../css/s/s-cmdjj4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pz5dirmwx"/><path class="s-cmdjj4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:table-shortcut" /></template>
