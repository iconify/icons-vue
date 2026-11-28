<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9mnawloe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9mnawloe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:vr-headset-solid" /></template>
