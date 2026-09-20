<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1a8dhblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1a8dhblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:namur-check-function-filled" /></template>
