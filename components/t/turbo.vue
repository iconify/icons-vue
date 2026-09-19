<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr8j-xj6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hr8j-xj6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:turbo" /></template>
