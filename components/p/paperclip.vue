<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4djbg3cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x4djbg3cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:paperclip" /></template>
