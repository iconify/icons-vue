<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz9m54bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="wz9m54bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-facebook" /></template>
