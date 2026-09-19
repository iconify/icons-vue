<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-95x3bia.css';
import '../../css/h/hdz9ffk6k.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 l-95x3bia"/><path class="clr-i-outline clr-i-outline-path-2 hdz9ffk6k"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:resize-up-line" /></template>
