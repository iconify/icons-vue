<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt5mbcb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt5mbcb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-fill" /></template>
