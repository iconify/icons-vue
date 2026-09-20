<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0m8wdw9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0m8wdw9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:time" /></template>
