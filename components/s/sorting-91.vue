<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb-rseb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-rseb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sorting-91" /></template>
