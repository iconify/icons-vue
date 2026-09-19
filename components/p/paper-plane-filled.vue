<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3a24bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm3a24bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:paper-plane-filled" /></template>
