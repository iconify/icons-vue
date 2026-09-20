<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c58_3zblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":120,"height":258};
const content = `<path class="c58_3zblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mongodb-light" /></template>
