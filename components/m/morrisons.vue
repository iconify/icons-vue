<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjx5_kvso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjx5_kvso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:morrisons" /></template>
