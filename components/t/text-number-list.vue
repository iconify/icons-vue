<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh020cc2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh020cc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-number-list" /></template>
