<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_86wrbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_86wrbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:readme" /></template>
