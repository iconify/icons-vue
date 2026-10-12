<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jttby2z2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jttby2z2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-quote" /></template>
