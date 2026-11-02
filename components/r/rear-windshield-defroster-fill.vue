<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m68lqw2ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m68lqw2ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rear-windshield-defroster-fill" /></template>
