<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlap_3_in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlap_3_in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:quotation-mark-solid" /></template>
