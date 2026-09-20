<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5-sr2nuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5-sr2nuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-only-one-to-only-one" /></template>
