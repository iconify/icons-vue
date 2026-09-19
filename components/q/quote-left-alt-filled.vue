<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw3py73bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw3py73bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:quote-left-alt-filled" /></template>
