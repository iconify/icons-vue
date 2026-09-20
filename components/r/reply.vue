<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onn7nldop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="onn7nldop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:reply" /></template>
