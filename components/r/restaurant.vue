<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr0v5zbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr0v5zbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:restaurant" /></template>
