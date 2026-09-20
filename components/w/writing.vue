<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1hn7mb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1hn7mb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:writing" /></template>
