<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auwx0p0zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auwx0p0zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:serenity-filled" /></template>
