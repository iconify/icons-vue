<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hen24fb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hen24fb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:swift" /></template>
