<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt9n4ob1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt9n4ob1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stroke-right" /></template>
