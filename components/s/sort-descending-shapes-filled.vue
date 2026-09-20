<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy8w78pep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy8w78pep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sort-descending-shapes-filled" /></template>
