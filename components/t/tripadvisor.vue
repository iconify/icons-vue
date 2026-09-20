<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wax-ynfkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wax-ynfkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tripadvisor" /></template>
