<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r37ut7cmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r37ut7cmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plug-x" /></template>
