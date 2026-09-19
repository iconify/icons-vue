<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdvz9kbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdvz9kbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:surfboard-filled" /></template>
