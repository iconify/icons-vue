<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joxi-ub2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="joxi-ub2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-reading-filled" /></template>
