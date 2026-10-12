<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0ncl5r7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0ncl5r7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tree-palm-filled" /></template>
