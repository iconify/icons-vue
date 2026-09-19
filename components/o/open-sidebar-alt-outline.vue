<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_tqjjm9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_tqjjm9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:open-sidebar-alt-outline" /></template>
