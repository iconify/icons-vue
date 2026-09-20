<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu6ju2buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xu6ju2buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-u-turn-right-fill" /></template>
