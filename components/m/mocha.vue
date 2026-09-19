<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhcgfebjd.css';
import '../../css/z/zmii52bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dhcgfebjd"/><path class="zmii52bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mocha" /></template>
