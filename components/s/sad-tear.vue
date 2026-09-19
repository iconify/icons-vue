<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd-v9xn1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="fd-v9xn1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sad-tear" /></template>
