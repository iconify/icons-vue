<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkul0jf2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dkul0jf2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:trophy" /></template>
