<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_7bycxnx.css';
import '../../css/u/uqzyn-kgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_7bycxnx"/><path class="uqzyn-kgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sushi" /></template>
