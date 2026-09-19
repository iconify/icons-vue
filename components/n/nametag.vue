<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl_2tsmqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nl_2tsmqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:nametag" /></template>
