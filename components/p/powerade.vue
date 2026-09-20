<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leae0xb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":184.84,"height":59.76};
const content = `<path class="leae0xb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:powerade" /></template>
