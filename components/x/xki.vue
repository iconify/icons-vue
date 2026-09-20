<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkj9tpb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkj9tpb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xki" /></template>
