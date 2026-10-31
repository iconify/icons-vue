<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gup0_nber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gup0_nber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-20-solid" /></template>
