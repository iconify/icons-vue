<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s73-gj2tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s73-gj2tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unfold-less-horizontal" /></template>
