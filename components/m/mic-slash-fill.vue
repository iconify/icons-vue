<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf73feb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qf73feb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:mic-slash-fill" /></template>
