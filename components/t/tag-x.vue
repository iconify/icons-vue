<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mycu2ya9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mycu2ya9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:tag-x" /></template>
