<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dghn0kt5a.css';
import '../../css/i/ioxby4bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dghn0kt5a"/><path class="ioxby4bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:reactrouter" /></template>
