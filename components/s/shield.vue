<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrzj-2bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qrzj-2bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:shield" /></template>
