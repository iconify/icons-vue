<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldll2qu4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldll2qu4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:slice-filled" /></template>
