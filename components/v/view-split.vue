<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8ektq0ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8ektq0ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:view-split" /></template>
