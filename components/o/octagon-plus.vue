<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6jlcpp_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6jlcpp_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon-plus" /></template>
