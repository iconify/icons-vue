<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe6u85bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qe6u85bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:triangle" /></template>
