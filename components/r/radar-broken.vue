<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s097pqpjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s097pqpjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radar-broken" /></template>
