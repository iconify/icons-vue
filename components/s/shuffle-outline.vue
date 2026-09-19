<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgk67bbts.css';
import '../../css/i/ixe8k5-3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgk67bbts"/><path class="ixe8k5-3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:shuffle-outline" /></template>
