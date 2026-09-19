<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er43i9stk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er43i9stk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rss" /></template>
