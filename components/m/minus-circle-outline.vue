<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wckr9kb1z.css';
import '../../css/n/n-u2bhuwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wckr9kb1z"/><path class="n-u2bhuwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:minus-circle-outline" /></template>
