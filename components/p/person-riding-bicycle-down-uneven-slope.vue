<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_12uccoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e_12uccoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-riding-bicycle-down-uneven-slope" /></template>
