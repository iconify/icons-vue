<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3xob38rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3xob38rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-right-04" /></template>
