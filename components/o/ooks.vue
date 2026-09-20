<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbiljer2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wbiljer2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ooks" /></template>
