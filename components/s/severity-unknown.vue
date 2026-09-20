<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm7lsubwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nm7lsubwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:severity-unknown" /></template>
