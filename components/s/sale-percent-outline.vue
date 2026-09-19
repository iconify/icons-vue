<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qihv1wb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qihv1wb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:sale-percent-outline" /></template>
