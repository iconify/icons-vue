<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi4wg5b2c.css';
import '../../css/o/obi015b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zi4wg5b2c"/><path class="obi015b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:materializecss" /></template>
