<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz-0psbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xz-0psbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-circle-badge-plus" /></template>
