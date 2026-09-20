<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoj6c4bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xoj6c4bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wallet-16" /></template>
