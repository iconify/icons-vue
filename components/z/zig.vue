<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spd74y6rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="spd74y6rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:zig" /></template>
