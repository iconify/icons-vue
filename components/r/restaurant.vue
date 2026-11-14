<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re8k9pb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re8k9pb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:restaurant" /></template>
