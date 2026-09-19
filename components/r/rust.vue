<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmgp09f-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hmgp09f-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rust" /></template>
