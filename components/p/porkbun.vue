<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvnkohbhv.css';
import '../../css/t/txu2pvbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvnkohbhv"/><path class="txu2pvbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:porkbun" /></template>
