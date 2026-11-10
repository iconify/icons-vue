<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czbr_75eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czbr_75eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-size" /></template>
