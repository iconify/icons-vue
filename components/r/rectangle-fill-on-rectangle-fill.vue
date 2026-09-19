<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zml9i3ljd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zml9i3ljd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-fill-on-rectangle-fill" /></template>
