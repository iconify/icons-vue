<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzdl1tzij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzdl1tzij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:transgender-filled" /></template>
