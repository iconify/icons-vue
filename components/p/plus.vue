<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1m7vvbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1m7vvbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:plus" /></template>
