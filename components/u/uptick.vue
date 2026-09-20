<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvbze2s-t.css';
import '../../css/j/j0zlpmbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvbze2s-t"/><path class="j0zlpmbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:uptick" /></template>
