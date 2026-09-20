<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugzybtvza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugzybtvza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wash-dry" /></template>
