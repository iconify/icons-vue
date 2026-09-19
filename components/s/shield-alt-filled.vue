<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v60k2obpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v60k2obpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shield-alt-filled" /></template>
