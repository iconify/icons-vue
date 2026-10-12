<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kza05hb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kza05hb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stretch-horizontal-filled" /></template>
