<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiwdgmb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aiwdgmb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shopping-bag-solid" /></template>
