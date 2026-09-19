<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dogrmo3cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dogrmo3cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:term-deposit-filled" /></template>
