<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4_i3vb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1800,"height":1800};
const content = `<path class="f4_i3vb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:resend-dark" /></template>
