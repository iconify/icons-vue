<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiqwlw-9v.css';
import '../../css/y/y3t9q1bdx.css';
import '../../css/c/c76eisdpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiqwlw-9v"/><path class="y3t9q1bdx"/><path class="c76eisdpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-id-card" /></template>
