<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3cll2epf.css';
import '../../css/w/w-wp2mbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u3cll2epf"/><path class="w-wp2mbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:typescript" /></template>
