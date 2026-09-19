<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqv2w248g.css';
import '../../css/v/vojqrkb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqv2w248g"/><path class="vojqrkb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tram" /></template>
