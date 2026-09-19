<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvnmchr1u.css';
import '../../css/z/z6avml47a.css';
import '../../css/p/pvttq6b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uvnmchr1u"/><path class="z6avml47a"/><path class="pvttq6b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:protractor" /></template>
