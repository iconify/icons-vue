<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnet0zdkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnet0zdkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:menorah-filled" /></template>
