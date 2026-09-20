<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6aj__i7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6aj__i7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rectangular-prism-off" /></template>
