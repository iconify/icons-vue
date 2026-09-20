<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kra6u_baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="kra6u_baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:skiing" /></template>
