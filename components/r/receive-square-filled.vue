<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx7x4ac0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx7x4ac0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receive-square-filled" /></template>
