<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjylu9y7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rjylu9y7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:xamarin" /></template>
