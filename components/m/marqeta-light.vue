<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im5fqoxyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":553.4,"height":78.9};
const content = `<path class="im5fqoxyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:marqeta-light" /></template>
