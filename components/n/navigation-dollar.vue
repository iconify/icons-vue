<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncqj-0diq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncqj-0diq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-dollar" /></template>
