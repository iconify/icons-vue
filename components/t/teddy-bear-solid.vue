<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go8zk9zko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go8zk9zko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:teddy-bear-solid" /></template>
