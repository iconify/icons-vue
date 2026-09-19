<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp0xqacie.css';
import '../../css/y/ycdb5-nqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fp0xqacie"/><path class="ycdb5-nqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:reflex" /></template>
