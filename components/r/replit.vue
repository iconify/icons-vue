<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9jc9z6kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="b9jc9z6kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:replit" /></template>
