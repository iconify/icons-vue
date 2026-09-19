<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvet51ejv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvet51ejv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wardrobe-02" /></template>
