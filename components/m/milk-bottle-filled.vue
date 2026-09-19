<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if7_acbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if7_acbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:milk-bottle-filled" /></template>
