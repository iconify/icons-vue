<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvpf93m0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vvpf93m0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-arrow-up-right-arrow-down-left-slash" /></template>
