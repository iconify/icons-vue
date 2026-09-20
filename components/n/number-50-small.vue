<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd6a3bk_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd6a3bk_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-50-small" /></template>
