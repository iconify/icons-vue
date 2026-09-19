<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqk2l_13t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqk2l_13t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:octagon-fill" /></template>
