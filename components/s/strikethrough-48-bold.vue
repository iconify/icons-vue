<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwnfq9ybn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cwnfq9ybn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:strikethrough-48-bold" /></template>
