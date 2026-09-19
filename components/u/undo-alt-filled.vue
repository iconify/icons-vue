<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shy0p6bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shy0p6bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:undo-alt-filled" /></template>
