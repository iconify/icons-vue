<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np0e99fbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np0e99fbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shopping-basket" /></template>
