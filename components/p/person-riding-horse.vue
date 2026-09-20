<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da9y1yr3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="da9y1yr3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-riding-horse" /></template>
