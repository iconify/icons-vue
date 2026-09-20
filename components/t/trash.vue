<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue2paxbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue2paxbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:trash" /></template>
