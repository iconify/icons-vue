<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew5er1t7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew5er1t7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pentagon" /></template>
