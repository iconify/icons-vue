<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzz9jcdew.css';
import '../../css/e/eler63bmi.css';
import '../../css/y/y2481-1dj.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 mzz9jcdew"/><path class="clr-i-outline clr-i-outline-path-2 eler63bmi"/><path class="clr-i-outline clr-i-outline-path-3 y2481-1dj"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:volume-up-line" /></template>
