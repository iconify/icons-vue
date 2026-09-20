<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j08t-ob-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j08t-ob-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-broken" /></template>
