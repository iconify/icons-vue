<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwci-tmql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwci-tmql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:menu-alt-1" /></template>
