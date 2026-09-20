<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp5ll4bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp5ll4bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget4-filled" /></template>
