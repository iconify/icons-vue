<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0hy2rb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0hy2rb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:objects-horizontal-left" /></template>
