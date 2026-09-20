<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5aj-_rmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s5aj-_rmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portnote-light" /></template>
