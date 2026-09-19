<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejwoc6wpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejwoc6wpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:polygon-filled" /></template>
