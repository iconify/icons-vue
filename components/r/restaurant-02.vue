<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teq_nobwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teq_nobwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:restaurant-02" /></template>
