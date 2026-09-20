<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sotyw2bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sotyw2bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:whisk-fork-knife" /></template>
