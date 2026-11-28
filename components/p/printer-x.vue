<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1rn0t1rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1rn0t1rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:printer-x" /></template>
