<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b68-ukb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b68-ukb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wifi-low-outline" /></template>
