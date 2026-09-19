<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae2_vkljg.css';
import '../../css/t/tubczkbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ae2_vkljg"/><path class="tubczkbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:notes" /></template>
