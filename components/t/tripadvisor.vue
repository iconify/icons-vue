<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qux8kuy1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1408};
const content = `<path class="qux8kuy1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:tripadvisor" /></template>
