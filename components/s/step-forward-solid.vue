<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv9me8bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bv9me8bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:step-forward-solid" /></template>
