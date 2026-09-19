<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/argsfhb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="argsfhb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-bag-off-filled" /></template>
