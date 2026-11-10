<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uga4pjbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uga4pjbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-heading-five" /></template>
