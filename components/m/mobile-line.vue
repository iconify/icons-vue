<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thnmxrwna.css';
import '../../css/t/th59x_bgi.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 thnmxrwna"/><path class="clr-i-outline clr-i-outline-path-2 th59x_bgi"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:mobile-line" /></template>
