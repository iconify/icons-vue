<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paxaq7ccy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paxaq7ccy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:minus-shield-filled" /></template>
