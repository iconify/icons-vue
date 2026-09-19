<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swny0lthw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swny0lthw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:pencil" /></template>
