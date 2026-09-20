<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glkde0b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="glkde0b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:signs-post-2" /></template>
