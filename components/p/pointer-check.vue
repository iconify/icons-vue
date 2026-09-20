<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stjjntb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stjjntb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-check" /></template>
