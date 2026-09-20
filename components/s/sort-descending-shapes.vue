<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eao8dbouc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eao8dbouc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sort-descending-shapes" /></template>
