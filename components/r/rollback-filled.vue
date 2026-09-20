<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdqx10g5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdqx10g5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:rollback-filled" /></template>
