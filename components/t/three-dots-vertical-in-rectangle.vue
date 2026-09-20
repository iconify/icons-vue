<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzgx5tmfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kzgx5tmfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-dots-vertical-in-rectangle" /></template>
