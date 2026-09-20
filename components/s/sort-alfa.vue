<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n48t9qb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n48t9qb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sort-alfa" /></template>
