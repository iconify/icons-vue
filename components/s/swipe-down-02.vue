<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo0n66b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo0n66b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-down-02" /></template>
