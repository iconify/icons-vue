<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r35m9-gnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r35m9-gnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:reorder-fill" /></template>
