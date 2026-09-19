<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdmdmob_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xdmdmob_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:timer-fill" /></template>
