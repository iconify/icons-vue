<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gigi96bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gigi96bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ooe" /></template>
