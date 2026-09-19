<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx5l_hbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx5l_hbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table-tennis-bat" /></template>
