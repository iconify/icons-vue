<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-vpl2b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-vpl2b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield" /></template>
