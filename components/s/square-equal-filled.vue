<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2_v2bbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2_v2bbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-equal-filled" /></template>
