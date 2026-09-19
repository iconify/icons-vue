<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ou0nb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o1ou0nb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tram" /></template>
