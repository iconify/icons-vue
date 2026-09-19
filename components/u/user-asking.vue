<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-3pvhb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-3pvhb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:user-asking" /></template>
