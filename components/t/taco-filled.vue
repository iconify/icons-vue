<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uya9hk5sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uya9hk5sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:taco-filled" /></template>
