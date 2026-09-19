<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4mag820m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="l4mag820m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-rectangle" /></template>
