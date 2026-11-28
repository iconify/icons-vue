<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxg-2ccoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxg-2ccoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pilcrow-right-solid" /></template>
