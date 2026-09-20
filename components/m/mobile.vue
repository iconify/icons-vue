<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex2jck8xh.css';
import '../../css/z/zdqlz_b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ex2jck8xh"/><path clip-rule="evenodd" class="zdqlz_b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:mobile" /></template>
