<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu2np_b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu2np_b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-3" /></template>
