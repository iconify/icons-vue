<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc1j5bc2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc1j5bc2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-bolt" /></template>
