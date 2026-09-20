<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtgmpjkvu.css';
import '../../css/k/kzggjzb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":800,"top":-38};
const content = `<path class="wtgmpjkvu"/><path class="kzggjzb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:unikoo" /></template>
