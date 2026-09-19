<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zawcu5--r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zawcu5--r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:smallcircle-fill-circle" /></template>
