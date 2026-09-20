<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cixcpjbxu.css';
import '../../css/m/mr5bnpbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cixcpjbxu"/><path class="mr5bnpbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wallos" /></template>
