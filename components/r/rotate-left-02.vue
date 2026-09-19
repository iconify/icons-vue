<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1w1en59s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1w1en59s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-left-02" /></template>
