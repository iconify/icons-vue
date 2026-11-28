<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agkfsk3zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agkfsk3zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:scale-balance" /></template>
