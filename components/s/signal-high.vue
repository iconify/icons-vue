<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b68na8seu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b68na8seu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:signal-high" /></template>
