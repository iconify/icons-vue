<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kslszo2im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kslszo2im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-down-fill" /></template>
