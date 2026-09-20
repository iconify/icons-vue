<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeceec92t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeceec92t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pier" /></template>
