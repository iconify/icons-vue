<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x37too4bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x37too4bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:video" /></template>
