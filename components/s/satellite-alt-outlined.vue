<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbs-nk3gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbs-nk3gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:satellite-alt-outlined" /></template>
