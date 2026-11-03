<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzt2iu9dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzt2iu9dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pill" /></template>
