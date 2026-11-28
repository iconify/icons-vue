<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi-5o3bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi-5o3bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:not-equal" /></template>
