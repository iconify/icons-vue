<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq2_-jbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq2_-jbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:rows" /></template>
