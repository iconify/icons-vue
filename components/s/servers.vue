<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijy3k1pdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijy3k1pdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:servers" /></template>
