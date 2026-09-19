<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n48w2aczu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n48w2aczu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:trash-full" /></template>
