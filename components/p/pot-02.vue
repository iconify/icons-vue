<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8tt_bjdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8tt_bjdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pot-02" /></template>
