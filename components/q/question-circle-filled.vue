<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bna3i2b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bna3i2b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:question-circle-filled" /></template>
