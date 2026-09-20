<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc2pc3bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1800,"height":1800};
const content = `<path class="tc2pc3bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:resend-light" /></template>
