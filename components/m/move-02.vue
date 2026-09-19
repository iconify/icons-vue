<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p82xa8l7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p82xa8l7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:move-02" /></template>
