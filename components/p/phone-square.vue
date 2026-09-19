<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f632bhb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f632bhb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:phone-square" /></template>
