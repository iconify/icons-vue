<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olsgh7b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="olsgh7b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:twitter" /></template>
