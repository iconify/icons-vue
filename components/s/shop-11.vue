<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1qp49bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="g1qp49bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:shop-11" /></template>
