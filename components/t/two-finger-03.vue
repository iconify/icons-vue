<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkv49fbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkv49fbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:two-finger-03" /></template>
