<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfa1y2pwb.css';
import '../../css/l/l_fae7rzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfa1y2pwb"/><path class="l_fae7rzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shredder-filled" /></template>
