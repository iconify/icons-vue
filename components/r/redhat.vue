<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if-22abir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="if-22abir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:redhat" /></template>
