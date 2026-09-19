<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stvv9dr8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stvv9dr8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:send-horizontal" /></template>
