<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjm_ikbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kjm_ikbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-numeric-down" /></template>
