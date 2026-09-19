<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykr98khrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykr98khrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shower-filled" /></template>
