<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfqbni7gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bfqbni7gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:motion" /></template>
