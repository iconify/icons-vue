<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksit7p2xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ksit7p2xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:thumbtack" /></template>
