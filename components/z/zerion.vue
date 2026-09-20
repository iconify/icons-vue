<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmpd8_b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wmpd8_b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zerion" /></template>
