<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh9g1wbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kh9g1wbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:oxy" /></template>
