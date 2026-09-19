<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_jn8tb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_jn8tb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tally-5" /></template>
