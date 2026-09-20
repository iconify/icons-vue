<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpx7c3bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpx7c3bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:testing-library" /></template>
