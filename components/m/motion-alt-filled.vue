<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj1psjbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj1psjbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:motion-alt-filled" /></template>
