<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwdulib5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hwdulib5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:money-bag-cny" /></template>
