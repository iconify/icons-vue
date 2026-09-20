<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddzjxeb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddzjxeb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:plus-one-increment-bold" /></template>
