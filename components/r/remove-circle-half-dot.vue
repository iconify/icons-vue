<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzaeyspsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzaeyspsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:remove-circle-half-dot" /></template>
