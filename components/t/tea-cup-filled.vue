<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3qeq8b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3qeq8b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tea-cup-filled" /></template>
