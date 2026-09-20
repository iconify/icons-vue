<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwexrpbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rwexrpbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:table-lamp-2" /></template>
