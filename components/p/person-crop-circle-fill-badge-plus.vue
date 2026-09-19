<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqukjzb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xqukjzb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-circle-fill-badge-plus" /></template>
