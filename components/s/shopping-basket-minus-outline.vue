<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov8ljqhgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov8ljqhgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shopping-basket-minus-outline" /></template>
