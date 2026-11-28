<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbp5g-0ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbp5g-0ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:store-clock" /></template>
