<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt5hs-bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt5hs-bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:open-source" /></template>
