<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e41hi2rog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e41hi2rog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:search-minus" /></template>
