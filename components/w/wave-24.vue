<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7xadxb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7xadxb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wave-24" /></template>
