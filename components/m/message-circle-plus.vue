<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufqvjm-rq.css';
import '../../css/f/fu72iwgtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufqvjm-rq"/><path class="fu72iwgtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-plus" /></template>
