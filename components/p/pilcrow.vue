<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se7ex_ekk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se7ex_ekk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pilcrow" /></template>
