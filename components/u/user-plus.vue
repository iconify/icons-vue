<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6we54yhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6we54yhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:user-plus" /></template>
