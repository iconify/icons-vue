<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkrny1bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkrny1bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stairs-01" /></template>
