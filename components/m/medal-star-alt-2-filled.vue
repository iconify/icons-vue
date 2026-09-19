<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y64_zlase.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y64_zlase"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medal-star-alt-2-filled" /></template>
