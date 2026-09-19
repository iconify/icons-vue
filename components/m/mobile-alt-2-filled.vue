<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptlzc4fda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptlzc4fda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mobile-alt-2-filled" /></template>
