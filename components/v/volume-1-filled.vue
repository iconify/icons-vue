<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8qfq31zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8qfq31zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:volume-1-filled" /></template>
