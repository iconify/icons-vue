<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8dq-qb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8dq-qb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-record-filled" /></template>
