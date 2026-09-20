<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvm7w0qkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvm7w0qkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:soundcloud-fill" /></template>
