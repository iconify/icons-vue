<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf7jojbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf7jojbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:scanner" /></template>
