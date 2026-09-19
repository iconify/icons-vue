<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n87f4mb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":850};
const content = `<path class="n87f4mb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:paypal" /></template>
