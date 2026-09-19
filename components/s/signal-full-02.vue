<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byqtep5bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byqtep5bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:signal-full-02" /></template>
