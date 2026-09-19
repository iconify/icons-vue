<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4t1ozb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t4t1ozb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pin-sharp" /></template>
