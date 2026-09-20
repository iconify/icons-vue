<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2111784r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2111784r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:maximize-square-filled" /></template>
