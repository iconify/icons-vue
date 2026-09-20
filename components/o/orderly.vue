<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf1lmlcvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vf1lmlcvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:orderly" /></template>
